<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbbtl_qtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dbbtl_qtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ikea-starkvind" {...props}></Icon>
