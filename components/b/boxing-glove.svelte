<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3blzff5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u3blzff5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:boxing-glove" {...props}></Icon>
