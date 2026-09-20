<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvghow68r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gvghow68r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:hotel-three-star-solid" {...props}></Icon>
