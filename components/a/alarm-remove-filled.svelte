<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fudag8bca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fudag8bca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:alarm-remove-filled" {...props}></Icon>
