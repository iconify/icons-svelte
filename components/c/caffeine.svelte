<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubeai9twx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubeai9twx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:caffeine" {...props}></Icon>
