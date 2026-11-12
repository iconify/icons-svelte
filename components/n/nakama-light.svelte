<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4nb21bnx.css';
import '../../css/d/dj-d89b_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s4nb21bnx"/><path class="dj-d89b_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nakama-light" {...props}></Icon>
