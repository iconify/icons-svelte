<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-ath0bga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c-ath0bga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:key-solid" {...props}></Icon>
