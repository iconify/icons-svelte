<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qslsf14ya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qslsf14ya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:1" {...props}></Icon>
