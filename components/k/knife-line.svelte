<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5g5nccdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5g5nccdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:knife-line" {...props}></Icon>
