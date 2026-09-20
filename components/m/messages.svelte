<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aewy_8bgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aewy_8bgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:messages" {...props}></Icon>
