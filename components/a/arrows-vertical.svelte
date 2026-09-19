<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4d0o9i5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4d0o9i5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:arrows-vertical" {...props}></Icon>
