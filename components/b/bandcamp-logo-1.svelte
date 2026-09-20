<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sogrj-bvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sogrj-bvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:bandcamp-logo-1" {...props}></Icon>
