<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atay87bmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":352,"height":512};
const content = `<path class="atay87bmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:label" {...props}></Icon>
