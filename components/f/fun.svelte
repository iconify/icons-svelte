<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzfcy-b5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mzfcy-b5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:fun" {...props}></Icon>
