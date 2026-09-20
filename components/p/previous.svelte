<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqb79jbms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqb79jbms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:previous" {...props}></Icon>
