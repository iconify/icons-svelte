<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa-h3mbql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oa-h3mbql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:friendica" {...props}></Icon>
