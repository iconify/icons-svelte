<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7_d7wiqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7_d7wiqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:double-quotes-r" {...props}></Icon>
