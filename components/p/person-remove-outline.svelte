<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w53752bty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w53752bty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:person-remove-outline" {...props}></Icon>
