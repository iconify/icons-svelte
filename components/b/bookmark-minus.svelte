<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpg076mjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qpg076mjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:bookmark-minus" {...props}></Icon>
