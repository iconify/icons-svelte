<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfkcbob-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":733,"height":1024};
const content = `<path class="cfkcbob-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:candycane" {...props}></Icon>
