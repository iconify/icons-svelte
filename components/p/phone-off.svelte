<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruhl7hcfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ruhl7hcfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:phone-off" {...props}></Icon>
