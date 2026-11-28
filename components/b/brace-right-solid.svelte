<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/is9lt_wff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="is9lt_wff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:brace-right-solid" {...props}></Icon>
