<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv8p7pohc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uv8p7pohc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:location-fill" {...props}></Icon>
