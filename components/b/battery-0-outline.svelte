<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sngn-6bwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sngn-6bwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:battery-0-outline" {...props}></Icon>
