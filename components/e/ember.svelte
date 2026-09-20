<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9v7t8xls.css';
import '../../css/o/os0e1fbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":213};
const content = `<path class="h9v7t8xls"/><path class="os0e1fbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ember" {...props}></Icon>
