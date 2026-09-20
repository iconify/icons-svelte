<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0l0jm5oq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0l0jm5oq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:flame-broken" {...props}></Icon>
