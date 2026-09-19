<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm0apjj5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xm0apjj5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:dental-floss" {...props}></Icon>
