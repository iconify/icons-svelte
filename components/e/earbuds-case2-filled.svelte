<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x27ye4o8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x27ye4o8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:earbuds-case2-filled" {...props}></Icon>
