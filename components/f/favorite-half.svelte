<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj_igdc0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bj_igdc0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:favorite-half" {...props}></Icon>
