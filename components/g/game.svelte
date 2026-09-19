<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blpq5rbmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="blpq5rbmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:game" {...props}></Icon>
