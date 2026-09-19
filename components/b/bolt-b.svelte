<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obr3sqb_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obr3sqb_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:bolt-b" {...props}></Icon>
