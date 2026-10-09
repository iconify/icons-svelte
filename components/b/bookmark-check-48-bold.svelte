<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7ue9wb8n.css';
import '../../css/s/shuuz6bqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b7ue9wb8n"/><path class="shuuz6bqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bookmark-check-48-bold" {...props}></Icon>
