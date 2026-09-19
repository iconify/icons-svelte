<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3k-h_bql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3k-h_bql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:exchange-solid" {...props}></Icon>
