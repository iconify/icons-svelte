<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5au4v4yb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u5au4v4yb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:align-justify" {...props}></Icon>
