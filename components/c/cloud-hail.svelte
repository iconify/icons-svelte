<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s12o5129x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s12o5129x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cloud-hail" {...props}></Icon>
