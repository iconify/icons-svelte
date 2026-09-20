<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cerp1lnii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cerp1lnii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:archive-outline" {...props}></Icon>
