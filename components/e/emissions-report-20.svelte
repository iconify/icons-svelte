<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezhonm73e.css';
import '../../css/w/wizc1jb8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ezhonm73e"/><path class="wizc1jb8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:emissions-report-20" {...props}></Icon>
