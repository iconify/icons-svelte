<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2hd4mbbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2hd4mbbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:currency-peso" {...props}></Icon>
