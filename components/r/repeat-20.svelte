<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8dyr0iia.css';
import '../../css/m/m1hyp0bms.css';
import '../../css/c/c02oijjub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m8dyr0iia"/><path class="m1hyp0bms"/><path class="c02oijjub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:repeat-20" {...props}></Icon>
