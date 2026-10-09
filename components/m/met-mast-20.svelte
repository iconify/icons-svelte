<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wn4zoubux.css';
import '../../css/w/wlwzuyb0k.css';
import '../../css/r/rv76zfbuo.css';
import '../../css/f/fzro0d78h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wn4zoubux"/><path class="wlwzuyb0k"/><path class="rv76zfbuo"/><path class="fzro0d78h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:met-mast-20" {...props}></Icon>
