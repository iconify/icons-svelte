<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-imqxbqc.css';
import '../../css/i/i6ih-jbst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b-imqxbqc"/><path class="i6ih-jbst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:air-conditioning-48-bold" {...props}></Icon>
