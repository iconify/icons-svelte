<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyce9obdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kyce9obdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:question-mark-circle-fill" {...props}></Icon>
