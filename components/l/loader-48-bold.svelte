<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2bvvkbzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q2bvvkbzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:loader-48-bold" {...props}></Icon>
