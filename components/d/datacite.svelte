<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oov1-gbqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oov1-gbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:datacite" {...props}></Icon>
