<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebzczoond.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebzczoond"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:arrows-horizontal-lines" {...props}></Icon>
