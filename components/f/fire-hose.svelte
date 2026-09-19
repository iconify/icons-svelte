<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf1zk3yha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bf1zk3yha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:fire-hose" {...props}></Icon>
