<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttwf1n2vk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ttwf1n2vk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:nuxt-js" {...props}></Icon>
