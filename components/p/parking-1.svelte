<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k18y-k1ul.css';
import '../../css/c/c4kqgrv6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k18y-k1ul"/><path class="c4kqgrv6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:parking-1" {...props}></Icon>
