<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqow5khri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqow5khri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:apostrophe" {...props}></Icon>
