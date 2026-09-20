<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_c0vp4vp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q_c0vp4vp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:paws-outline" {...props}></Icon>
