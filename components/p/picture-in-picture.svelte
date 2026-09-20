<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6kk9dbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6kk9dbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:picture-in-picture" {...props}></Icon>
