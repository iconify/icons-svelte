<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql0ag-0by.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ql0ag-0by"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:experts-exchange" {...props}></Icon>
