<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iecywpk1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iecywpk1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:dollar-circle" {...props}></Icon>
