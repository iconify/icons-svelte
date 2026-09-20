<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3p_plb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e3p_plb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:invoice-filled" {...props}></Icon>
