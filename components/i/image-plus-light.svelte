<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thkzaxbzw.css';
import '../../css/y/ytcirkb0g.css';
import '../../css/y/yekhwhkwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thkzaxbzw"/><path class="ytcirkb0g"/><path class="yekhwhkwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:image-plus-light" {...props}></Icon>
