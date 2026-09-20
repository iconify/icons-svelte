<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vaiqf7u2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vaiqf7u2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:battle-net" {...props}></Icon>
