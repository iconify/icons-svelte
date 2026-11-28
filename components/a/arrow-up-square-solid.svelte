<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg0h9qbfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lg0h9qbfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-up-square-solid" {...props}></Icon>
