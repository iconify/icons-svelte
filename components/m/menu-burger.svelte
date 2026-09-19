<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afkrn8b6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afkrn8b6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:menu-burger" {...props}></Icon>
