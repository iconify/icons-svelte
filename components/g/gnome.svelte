<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwjft7bhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwjft7bhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:gnome" {...props}></Icon>
