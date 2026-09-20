<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ektnvzbys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ektnvzbys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:baserow-dark" {...props}></Icon>
