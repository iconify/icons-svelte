<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsmx--e1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wsmx--e1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:claudecode" {...props}></Icon>
