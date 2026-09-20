<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhup8hb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhup8hb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:droplet-filled" {...props}></Icon>
