<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp0_6tmzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wp0_6tmzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-radio-button-on" {...props}></Icon>
