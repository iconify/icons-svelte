<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqcuhhb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqcuhhb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:flag-line" {...props}></Icon>
