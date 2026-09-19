<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0e22bbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0e22bbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:last-page" {...props}></Icon>
