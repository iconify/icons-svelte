<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy7mig5by.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cy7mig5by"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-square-code-fill" {...props}></Icon>
