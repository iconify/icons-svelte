<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8nalnb6j.css';
import '../../css/z/z89mqybmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o8nalnb6j"/><path class="z89mqybmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:qa-1x1" {...props}></Icon>
