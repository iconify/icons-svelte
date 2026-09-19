<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j942-bbxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j942-bbxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:generate-image-filled" {...props}></Icon>
