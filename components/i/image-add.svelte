<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yibyn6bhe.css';
import '../../css/f/fxqkr7b2w.css';
import '../../css/v/viznwcc0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yibyn6bhe"/><path class="fxqkr7b2w"/><path class="viznwcc0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:image-add" {...props}></Icon>
