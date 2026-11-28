<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t51abbooa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t51abbooa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:clipboard-list-x" {...props}></Icon>
