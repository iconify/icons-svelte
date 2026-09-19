<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ych81ffjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ych81ffjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:info-octagon-filled" {...props}></Icon>
