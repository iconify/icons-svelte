<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnlctj5oi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jnlctj5oi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:astroluma-dark" {...props}></Icon>
