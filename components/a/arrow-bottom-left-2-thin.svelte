<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiemr6b8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aiemr6b8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-bottom-left-2-thin" {...props}></Icon>
