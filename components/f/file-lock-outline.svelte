<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o26r6hdrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o26r6hdrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-lock-outline" {...props}></Icon>
