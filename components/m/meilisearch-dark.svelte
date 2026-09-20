<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eood56b1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eood56b1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:meilisearch-dark" {...props}></Icon>
