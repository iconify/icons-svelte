<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgmhddevn.css';
import '../../css/p/pw47icbmy.css';
import '../../css/c/cb4hdplqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="lgmhddevn"/><path class="pw47icbmy"/><path class="cb4hdplqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-view-alt" {...props}></Icon>
