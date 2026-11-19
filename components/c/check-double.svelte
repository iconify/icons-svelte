<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nplz0_bdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nplz0_bdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:check-double" {...props}></Icon>
