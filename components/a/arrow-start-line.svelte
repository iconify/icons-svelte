<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xemez9bmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xemez9bmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:arrow-start-line" {...props}></Icon>
