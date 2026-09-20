<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq-e0mx3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tq-e0mx3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:brightness-low-solid" {...props}></Icon>
