<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsf1w7y6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zsf1w7y6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:package-arrow-right-sharp" {...props}></Icon>
