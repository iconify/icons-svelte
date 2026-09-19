<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-lao_bir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m-lao_bir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:people" {...props}></Icon>
