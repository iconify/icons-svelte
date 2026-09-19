<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szew_ymuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="szew_ymuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:list" {...props}></Icon>
