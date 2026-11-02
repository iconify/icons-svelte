<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v15yy0bez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v15yy0bez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ease-in-fill" {...props}></Icon>
