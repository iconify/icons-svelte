<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmbk2pjqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmbk2pjqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:align-vertical-distribute" {...props}></Icon>
