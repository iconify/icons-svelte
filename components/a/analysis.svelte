<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdrc-op-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pdrc-op-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:analysis" {...props}></Icon>
