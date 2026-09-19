<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm5f1qe_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="dm5f1qe_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:fort-awesome-alt" {...props}></Icon>
