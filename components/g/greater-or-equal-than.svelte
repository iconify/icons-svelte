<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yatn-bc3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yatn-bc3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:greater-or-equal-than" {...props}></Icon>
