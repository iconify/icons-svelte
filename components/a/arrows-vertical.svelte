<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym31sab_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ym31sab_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:arrows-vertical" {...props}></Icon>
