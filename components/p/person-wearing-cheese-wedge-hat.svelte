<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3xg_yztz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v3xg_yztz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-wearing-cheese-wedge-hat" {...props}></Icon>
