<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4nfscq4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="q4nfscq4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pulsar" {...props}></Icon>
