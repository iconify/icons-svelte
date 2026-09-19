<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt8dqmswc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kt8dqmswc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:modula-2" {...props}></Icon>
