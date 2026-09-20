<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr6h1qbfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fr6h1qbfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:asterisk" {...props}></Icon>
