<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id3pb8bcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="id3pb8bcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:database-eye-off" {...props}></Icon>
