<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw-5d-bur.css';
import '../../css/i/iox2jrb0a.css';
import '../../css/g/ghxkzbb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tw-5d-bur"/><path class="iox2jrb0a"/><path class="ghxkzbb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:connector-ccs-20" {...props}></Icon>
