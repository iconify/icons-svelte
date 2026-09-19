<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs6eumz8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xs6eumz8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:iron-three" {...props}></Icon>
