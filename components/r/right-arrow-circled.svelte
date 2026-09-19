<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxv29_lqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="kxv29_lqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:right-arrow-circled" {...props}></Icon>
