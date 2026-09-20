<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy4cpbyhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cy4cpbyhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:headset-outline" {...props}></Icon>
