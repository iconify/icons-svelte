<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8k2-tb-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="j8k2-tb-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:face-with-no-good-gesture" {...props}></Icon>
