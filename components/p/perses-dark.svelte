<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oawho9b5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oawho9b5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:perses-dark" {...props}></Icon>
