<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev_uos1kn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ev_uos1kn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:arrows-end" {...props}></Icon>
