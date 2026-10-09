<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhvqtnbfx.css';
import '../../css/u/un5h_vbqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uhvqtnbfx"/><path class="un5h_vbqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:anemometer-48-bold" {...props}></Icon>
