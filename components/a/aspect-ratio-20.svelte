<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co0vf9bvy.css';
import '../../css/y/y91t96b3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="co0vf9bvy"/><path class="y91t96b3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:aspect-ratio-20" {...props}></Icon>
