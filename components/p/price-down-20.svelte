<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lae2_dgov.css';
import '../../css/a/ah8_uokdg.css';
import '../../css/n/nunhi4evw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lae2_dgov"/><path class="ah8_uokdg"/><path class="nunhi4evw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:price-down-20" {...props}></Icon>
