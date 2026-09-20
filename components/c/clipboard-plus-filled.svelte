<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2hlc7b8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2hlc7b8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:clipboard-plus-filled" {...props}></Icon>
