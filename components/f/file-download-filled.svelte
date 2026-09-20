<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl3zozbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vl3zozbpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:file-download-filled" {...props}></Icon>
