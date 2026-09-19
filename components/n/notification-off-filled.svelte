<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4a9j8b8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f4a9j8b8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:notification-off-filled" {...props}></Icon>
