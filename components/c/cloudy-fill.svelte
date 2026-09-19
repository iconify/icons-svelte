<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kou9hf2_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kou9hf2_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cloudy-fill" {...props}></Icon>
