<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c__xhlbcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="c__xhlbcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ambulatory-clinic" {...props}></Icon>
