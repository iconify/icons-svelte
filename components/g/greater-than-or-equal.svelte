<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7k3_bari.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7k3_bari"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:greater-than-or-equal" {...props}></Icon>
