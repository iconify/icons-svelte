<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezx0-pv8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ezx0-pv8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:camera-square-outline" {...props}></Icon>
