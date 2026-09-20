<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re-9-t6rq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="re-9-t6rq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:meilisearch-light" {...props}></Icon>
