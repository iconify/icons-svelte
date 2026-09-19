<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcd3_ql_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fcd3_ql_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-left-sm" {...props}></Icon>
