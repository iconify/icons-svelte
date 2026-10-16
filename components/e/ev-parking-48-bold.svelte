<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh8gpb9au.css';
import '../../css/o/op_jlg5nw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vh8gpb9au"/><path class="op_jlg5nw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ev-parking-48-bold" {...props}></Icon>
