<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayn4fno-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ayn4fno-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:credit-card-bold" {...props}></Icon>
