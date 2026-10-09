<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzb20mb_q.css';
import '../../css/i/ip69v-b7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bzb20mb_q"/><path class="ip69v-b7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:a-frame-48-bold" {...props}></Icon>
