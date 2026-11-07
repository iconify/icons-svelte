<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy2y5qfqd.css';
import '../../css/v/v3iz6x59v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qy2y5qfqd"/><path class="v3iz6x59v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bookmark-minus-bold-duotone" {...props}></Icon>
