<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t18nv0b9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="t18nv0b9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:balance-scale-left" {...props}></Icon>
