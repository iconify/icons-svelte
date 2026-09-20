<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwqzg0boz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zwqzg0boz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:joplin-light" {...props}></Icon>
