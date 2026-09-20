<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyudesphd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yyudesphd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:heart-discount" {...props}></Icon>
