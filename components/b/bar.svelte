<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4q6f6bqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e4q6f6bqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:bar" {...props}></Icon>
