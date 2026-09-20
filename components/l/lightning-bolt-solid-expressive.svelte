<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udzsqrbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udzsqrbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:lightning-bolt-solid-expressive" {...props}></Icon>
