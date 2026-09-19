<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab4ppporb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ab4ppporb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:lock-keyhole-open" {...props}></Icon>
