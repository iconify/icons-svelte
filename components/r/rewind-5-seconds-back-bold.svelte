<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikfqmnb8s.css';
import '../../css/a/a4x15ccoa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikfqmnb8s"/><path class="a4x15ccoa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rewind-5-seconds-back-bold" {...props}></Icon>
