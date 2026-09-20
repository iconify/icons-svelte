<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6kvmhbwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-2};
const content = `<path class="s6kvmhbwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:foursquare" {...props}></Icon>
