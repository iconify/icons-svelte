<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msn7i-v-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="msn7i-v-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-left-square-fill" {...props}></Icon>
