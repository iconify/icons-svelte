<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-0a_5-7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v-0a_5-7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:pause-circle-fill" {...props}></Icon>
