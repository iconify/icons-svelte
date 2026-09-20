<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj5vzgbfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vj5vzgbfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:flood-dark" {...props}></Icon>
