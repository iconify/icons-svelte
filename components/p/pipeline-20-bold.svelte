<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw9dp8bid.css';
import '../../css/k/k8w-7fbni.css';
import '../../css/o/o-hjr9b_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yw9dp8bid"/><path class="k8w-7fbni"/><path class="o-hjr9b_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pipeline-20-bold" {...props}></Icon>
