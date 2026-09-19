<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbih5wbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mbih5wbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:dollar" {...props}></Icon>
