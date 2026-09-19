<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhsc1vb_v.css';
import '../../css/w/wpob71b5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="dhsc1vb_v"/><path class="wpob71b5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:netbox" {...props}></Icon>
