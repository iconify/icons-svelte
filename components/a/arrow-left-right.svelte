<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag-g8fbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ag-g8fbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-left-right" {...props}></Icon>
