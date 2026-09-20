<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_bmafnne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_bmafnne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:alarm-warning-fill" {...props}></Icon>
