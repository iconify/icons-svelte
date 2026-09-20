<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aeepo1bji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aeepo1bji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:replay-sharp" {...props}></Icon>
