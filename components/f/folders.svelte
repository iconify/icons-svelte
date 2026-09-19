<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r59x8o_6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r59x8o_6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:folders" {...props}></Icon>
