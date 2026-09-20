<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr7rw0bnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="dr7rw0bnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:database" {...props}></Icon>
