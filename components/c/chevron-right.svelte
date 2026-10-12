<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdsdmgr9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wdsdmgr9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:chevron-right" {...props}></Icon>
