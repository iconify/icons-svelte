<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqm2fd0cl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqm2fd0cl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:file-records-fill" {...props}></Icon>
