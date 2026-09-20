<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2_v7mbej.css';
import '../../css/c/c2qxqnb8p.css';
import '../../css/h/h6l-atboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v2_v7mbej"/><path class="c2qxqnb8p"/><rect class="h6l-atboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:home-duotone" {...props}></Icon>
