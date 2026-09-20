<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0jrkyu8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y0jrkyu8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bag-alt-outline" {...props}></Icon>
