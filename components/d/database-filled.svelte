<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1-5z9b-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x1-5z9b-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:database-filled" {...props}></Icon>
