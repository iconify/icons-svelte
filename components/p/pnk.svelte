<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly55abcxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ly55abcxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:pnk" {...props}></Icon>
