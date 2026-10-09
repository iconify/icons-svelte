<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbytv9biz.css';
import '../../css/i/ifxacxt9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dbytv9biz"/><path class="ifxacxt9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:power-48-bold" {...props}></Icon>
