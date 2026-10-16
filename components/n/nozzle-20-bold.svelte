<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev392zb0m.css';
import '../../css/i/iusq5pwib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ev392zb0m"/><path class="iusq5pwib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:nozzle-20-bold" {...props}></Icon>
