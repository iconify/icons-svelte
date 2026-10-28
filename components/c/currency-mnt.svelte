<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uer13d1nq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uer13d1nq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:currency-mnt" {...props}></Icon>
