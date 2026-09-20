<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khr67rxkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="khr67rxkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:nextjs-outline" {...props}></Icon>
