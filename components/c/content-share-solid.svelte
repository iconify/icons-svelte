<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqd3vf-lu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqd3vf-lu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:content-share-solid" {...props}></Icon>
