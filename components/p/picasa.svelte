<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3dvt7jpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q3dvt7jpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:picasa" {...props}></Icon>
