<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s42005nyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s42005nyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:filter-slash" {...props}></Icon>
