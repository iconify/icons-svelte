<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2oipd3ky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="e2oipd3ky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:check-square" {...props}></Icon>
