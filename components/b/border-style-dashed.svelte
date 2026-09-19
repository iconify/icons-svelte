<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/purru6rav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="purru6rav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:border-style-dashed" {...props}></Icon>
