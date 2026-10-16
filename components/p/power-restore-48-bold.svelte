<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9rw-n5ub.css';
import '../../css/j/jfwsknlsh.css';
import '../../css/v/vqjgpvl-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a9rw-n5ub"/><path class="jfwsknlsh"/><path class="vqjgpvl-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:power-restore-48-bold" {...props}></Icon>
