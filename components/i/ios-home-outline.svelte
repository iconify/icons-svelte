<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmbmz2bey.css';
import '../../css/h/h4npctbsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tmbmz2bey"/><path class="h4npctbsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-home-outline" {...props}></Icon>
