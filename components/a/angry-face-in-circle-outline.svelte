<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlbbljj-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mlbbljj-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:angry-face-in-circle-outline" {...props}></Icon>
