<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic049nbdu.css';
import '../../css/u/ulq1acb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ic049nbdu"/><path class="ulq1acb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:business" {...props}></Icon>
