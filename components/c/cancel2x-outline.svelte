<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm_nw-iud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zm_nw-iud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:cancel2x-outline" {...props}></Icon>
