<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdf88uoew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cdf88uoew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cog" {...props}></Icon>
