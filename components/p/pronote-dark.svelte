<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6q_kacyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f6q_kacyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pronote-dark" {...props}></Icon>
