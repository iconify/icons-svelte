<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egv8nrbut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egv8nrbut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:n8n" {...props}></Icon>
