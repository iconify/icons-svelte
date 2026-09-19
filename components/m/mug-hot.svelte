<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzcrhv3ky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jzcrhv3ky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:mug-hot" {...props}></Icon>
