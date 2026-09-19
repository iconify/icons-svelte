<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1bwu8bhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q1bwu8bhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:molecule" {...props}></Icon>
