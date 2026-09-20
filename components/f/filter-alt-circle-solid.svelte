<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c75g7nqit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c75g7nqit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:filter-alt-circle-solid" {...props}></Icon>
