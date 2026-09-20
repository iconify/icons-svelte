<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvqusacuk.css';
import '../../css/r/rx6x0jbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvqusacuk"/><path class="rx6x0jbia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:filter-alt-circle" {...props}></Icon>
