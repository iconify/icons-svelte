<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au6hk9bdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="au6hk9bdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:crosshair" {...props}></Icon>
