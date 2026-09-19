<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u29vskbhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u29vskbhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dock-top-left-filled" {...props}></Icon>
