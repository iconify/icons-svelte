<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag8av007b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ag8av007b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:entrance-line" {...props}></Icon>
