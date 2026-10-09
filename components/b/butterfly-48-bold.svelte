<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkze5mbgn.css';
import '../../css/v/vkaih402o.css';
import '../../css/w/wqgk4rban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kkze5mbgn"/><path class="vkaih402o"/><path class="wqgk4rban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:butterfly-48-bold" {...props}></Icon>
