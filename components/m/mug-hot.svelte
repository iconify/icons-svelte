<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehxt69wsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ehxt69wsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:mug-hot" {...props}></Icon>
