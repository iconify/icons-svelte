<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-0j0rbiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y-0j0rbiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:recipesage" {...props}></Icon>
