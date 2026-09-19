<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct12hn0tg.css';
import '../../css/i/im4c1bc7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ct12hn0tg duoicon-secondary-layer"/><path class="duoicon-primary-layer im4c1bc7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:bookmark" {...props}></Icon>
