<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9mifv0qp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w9mifv0qp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:docktail-dark" {...props}></Icon>
