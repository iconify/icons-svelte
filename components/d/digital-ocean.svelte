<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajrmk5k8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ajrmk5k8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:digital-ocean" {...props}></Icon>
