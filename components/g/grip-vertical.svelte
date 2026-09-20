<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms-gnf8qd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ms-gnf8qd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:grip-vertical" {...props}></Icon>
