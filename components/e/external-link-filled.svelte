<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juul3ub7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="juul3ub7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:external-link-filled" {...props}></Icon>
