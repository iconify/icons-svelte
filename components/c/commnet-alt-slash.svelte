<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ootklr19s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ootklr19s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:commnet-alt-slash" {...props}></Icon>
