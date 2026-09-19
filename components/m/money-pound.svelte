<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5pm_acgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="v5pm_acgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:money-pound" {...props}></Icon>
