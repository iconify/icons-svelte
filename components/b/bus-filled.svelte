<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md6o_9v8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="md6o_9v8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:bus-filled" {...props}></Icon>
