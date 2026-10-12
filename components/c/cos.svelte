<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g99mf4bcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g99mf4bcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:cos" {...props}></Icon>
