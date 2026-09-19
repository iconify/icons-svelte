<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfwjc_bdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yfwjc_bdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:hashtag" {...props}></Icon>
