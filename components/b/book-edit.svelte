<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6jpv1b2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6jpv1b2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:book-edit" {...props}></Icon>
