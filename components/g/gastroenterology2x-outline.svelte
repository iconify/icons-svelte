<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b74xzvbhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="b74xzvbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:gastroenterology2x-outline" {...props}></Icon>
