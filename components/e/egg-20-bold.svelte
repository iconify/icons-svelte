<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7cj1cc1l.css';
import '../../css/e/exm6e72le.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v7cj1cc1l"/><path class="exm6e72le"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:egg-20-bold" {...props}></Icon>
