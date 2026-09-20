<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1e2dfvwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c1e2dfvwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:pen-solid" {...props}></Icon>
