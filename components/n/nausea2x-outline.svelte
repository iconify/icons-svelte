<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqe6q6hbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fqe6q6hbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:nausea2x-outline" {...props}></Icon>
