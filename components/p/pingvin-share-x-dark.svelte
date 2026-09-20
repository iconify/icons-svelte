<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td9bw8nuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="td9bw8nuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pingvin-share-x-dark" {...props}></Icon>
