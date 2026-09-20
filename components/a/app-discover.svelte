<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8ubvfbil.css';
import '../../css/u/uyme-uvxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f8ubvfbil ouiIcon__fillSecondary"/><path class="uyme-uvxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-discover" {...props}></Icon>
