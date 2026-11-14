<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwh8snbkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwh8snbkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="struq:menu" {...props}></Icon>
