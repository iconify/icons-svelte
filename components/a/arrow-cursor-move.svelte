<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh08u7trk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kh08u7trk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:arrow-cursor-move" {...props}></Icon>
