<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5tmxtvdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="r5tmxtvdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:amazon-pay" {...props}></Icon>
