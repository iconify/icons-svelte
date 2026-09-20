<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygcac9taj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ygcac9taj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:revel-light" {...props}></Icon>
