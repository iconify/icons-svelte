<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nivi21b7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nivi21b7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:bandsintown" {...props}></Icon>
