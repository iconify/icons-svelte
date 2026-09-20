<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdxcr6b2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fdxcr6b2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:map-search-solid" {...props}></Icon>
