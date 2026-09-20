<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr0d0kx5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yr0d0kx5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:cake-solid" {...props}></Icon>
