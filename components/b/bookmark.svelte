<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adz4t67qb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adz4t67qb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:bookmark" {...props}></Icon>
