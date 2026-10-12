<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwu1q-4-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwu1q-4-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:not-member-of" {...props}></Icon>
