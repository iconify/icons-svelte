<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8j1_70vb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y8j1_70vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:contrast" {...props}></Icon>
