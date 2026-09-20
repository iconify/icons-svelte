<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-zhl_bfp.css';
import '../../css/y/ytcirkb0g.css';
import '../../css/y/yekhwhkwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-zhl_bfp"/><path class="ytcirkb0g"/><path class="yekhwhkwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:image-minus-light" {...props}></Icon>
