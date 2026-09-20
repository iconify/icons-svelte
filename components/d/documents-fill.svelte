<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6lrkw5fu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6lrkw5fu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:documents-fill" {...props}></Icon>
