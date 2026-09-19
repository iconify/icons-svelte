<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-8yvxbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="v-8yvxbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:generic-scan" {...props}></Icon>
