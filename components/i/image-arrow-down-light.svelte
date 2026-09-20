<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytcirkb0g.css';
import '../../css/n/nctt2tb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytcirkb0g"/><path class="nctt2tb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:image-arrow-down-light" {...props}></Icon>
