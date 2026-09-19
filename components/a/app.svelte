<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxxg56hwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":731};
const content = `<path class="gxxg56hwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:app" {...props}></Icon>
