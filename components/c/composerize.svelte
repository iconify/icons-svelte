<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bggzpxb-r.css';
import '../../css/v/v-7fu2bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bggzpxb-r"/><path class="v-7fu2bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:composerize" {...props}></Icon>
