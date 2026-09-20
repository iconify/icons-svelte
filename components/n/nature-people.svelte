<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npiauk8yb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npiauk8yb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:nature-people" {...props}></Icon>
