<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq1no1b7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="bq1no1b7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:b-outline" {...props}></Icon>
