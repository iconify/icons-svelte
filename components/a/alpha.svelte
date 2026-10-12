<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn_nkmwfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hn_nkmwfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:alpha" {...props}></Icon>
