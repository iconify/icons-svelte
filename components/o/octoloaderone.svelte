<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9cnlsc3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="o9cnlsc3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:octoloaderone" {...props}></Icon>
