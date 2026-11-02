<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txjtudu8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txjtudu8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-2-fill" {...props}></Icon>
