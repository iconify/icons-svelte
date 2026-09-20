<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uau_mgktq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uau_mgktq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:exclamation-small-outline" {...props}></Icon>
