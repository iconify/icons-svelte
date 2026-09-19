<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcynyx-7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dcynyx-7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:notification-alert" {...props}></Icon>
