<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbu-t6btd.css';
import '../../css/u/use3a0b1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kbu-t6btd"/><path class="use3a0b1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevron-right-square-48-bold" {...props}></Icon>
