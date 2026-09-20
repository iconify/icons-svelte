<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js6e4_b-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="js6e4_b-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:monitor" {...props}></Icon>
