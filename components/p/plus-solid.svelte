<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ww1mpb9-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ww1mpb9-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:plus-solid" {...props}></Icon>
