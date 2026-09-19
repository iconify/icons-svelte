<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x__g1-fnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x__g1-fnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:close-circle-1-fill" {...props}></Icon>
