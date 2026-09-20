<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8yer9j0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5.5,"top":-2};
const content = `<path class="h8yer9j0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:deviantart" {...props}></Icon>
