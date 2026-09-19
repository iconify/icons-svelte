<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5f75abtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n5f75abtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:lastfm2" {...props}></Icon>
