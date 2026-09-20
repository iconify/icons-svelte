<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u576o3b_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u576o3b_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:hdx" {...props}></Icon>
