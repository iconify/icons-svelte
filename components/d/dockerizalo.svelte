<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgkqhtgri.css';
import '../../css/e/enl7e7b7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lgkqhtgri"/><path class="enl7e7b7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dockerizalo" {...props}></Icon>
