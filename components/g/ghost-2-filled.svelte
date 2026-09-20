<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urxzsob5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urxzsob5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ghost-2-filled" {...props}></Icon>
