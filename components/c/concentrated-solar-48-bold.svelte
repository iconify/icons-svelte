<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1xalrahn.css';
import '../../css/r/rb010diqx.css';
import '../../css/i/ijqqz3eok.css';
import '../../css/l/lo883k-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f1xalrahn"/><path class="rb010diqx"/><path class="ijqqz3eok"/><path class="lo883k-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:concentrated-solar-48-bold" {...props}></Icon>
