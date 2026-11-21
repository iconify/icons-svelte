<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhskqhuhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fhskqhuhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:docker-2017" {...props}></Icon>
