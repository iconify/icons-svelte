<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuoev4j6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="vuoev4j6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:android-solid" {...props}></Icon>
