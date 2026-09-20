<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-nq0ebna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-nq0ebna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:dots-horizontal" {...props}></Icon>
