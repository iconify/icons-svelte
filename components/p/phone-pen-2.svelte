<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gee7l6brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gee7l6brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:phone-pen-2" {...props}></Icon>
