<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwd_1frdz.css';
import '../../css/b/bcr3mblqh.css';
import '../../css/y/yekhwhkwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qwd_1frdz"/><path class="bcr3mblqh"/><path class="yekhwhkwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:image-times-light" {...props}></Icon>
