<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_yqxhbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_yqxhbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:bomb" {...props}></Icon>
