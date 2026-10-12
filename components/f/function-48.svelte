<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqboyjbcd.css';
import '../../css/k/ktpj8ab8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bqboyjbcd"/><path class="ktpj8ab8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:function-48" {...props}></Icon>
