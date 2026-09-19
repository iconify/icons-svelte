<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwqvxrvgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gwqvxrvgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:right-angle" {...props}></Icon>
