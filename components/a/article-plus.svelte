<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bs85jub3t.css';
import '../../css/x/xs84k4bav.css';
import '../../css/n/n-c0l9fka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bs85jub3t"/><path clip-rule="evenodd" class="xs84k4bav"/><path class="n-c0l9fka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:article-plus" {...props}></Icon>
