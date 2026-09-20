<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epjfojbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="epjfojbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:directus-light" {...props}></Icon>
