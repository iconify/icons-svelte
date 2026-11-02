<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x58o06ccs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x58o06ccs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-panel-left-fill" {...props}></Icon>
