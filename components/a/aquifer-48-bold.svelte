<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alk5rr8yk.css';
import '../../css/n/nhgdse76r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="alk5rr8yk"/><path class="nhgdse76r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:aquifer-48-bold" {...props}></Icon>
