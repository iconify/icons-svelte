<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo3caibxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wo3caibxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mic-2-line" {...props}></Icon>
