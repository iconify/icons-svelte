<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg46avbzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mg46avbzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-behind-barred-window" {...props}></Icon>
