<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbu-t6btd.css';
import '../../css/w/wou0m8doy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kbu-t6btd"/><path class="wou0m8doy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:minus-square-48-bold" {...props}></Icon>
