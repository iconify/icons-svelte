<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-bloh7bh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-bloh7bh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:angle-double-up" {...props}></Icon>
