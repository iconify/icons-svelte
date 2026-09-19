<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn6bq-bwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":432};
const content = `<path class="cn6bq-bwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:drink" {...props}></Icon>
