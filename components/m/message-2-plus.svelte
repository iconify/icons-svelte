<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygyzlvcpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygyzlvcpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-2-plus" {...props}></Icon>
