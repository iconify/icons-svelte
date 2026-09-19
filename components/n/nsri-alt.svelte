<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnjdskbit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":355,"height":512};
const content = `<path clip-rule="evenodd" class="rnjdskbit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:nsri-alt" {...props}></Icon>
