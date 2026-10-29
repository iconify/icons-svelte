<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1em_ve-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1em_ve-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-minus-corner" {...props}></Icon>
