<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi4f11bjo.css';
import '../../css/e/eycsbubwb.css';
import '../../css/z/z4z9i4luq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wi4f11bjo"/><path class="eycsbubwb"/><path class="z4z9i4luq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:rainbow" {...props}></Icon>
