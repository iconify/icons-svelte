<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp6o6tbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mp6o6tbvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:close-small" {...props}></Icon>
