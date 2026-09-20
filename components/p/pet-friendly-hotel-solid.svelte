<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyl-0kw5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iyl-0kw5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:pet-friendly-hotel-solid" {...props}></Icon>
