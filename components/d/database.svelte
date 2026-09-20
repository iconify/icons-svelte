<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4_mr3l7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4_mr3l7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:database" {...props}></Icon>
