<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9ps03s-o.css';
import '../../css/q/q0ooqm0dp.css';
import '../../css/h/hcg44lb5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y9ps03s-o"/><path class="q0ooqm0dp"/><path class="hcg44lb5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:report-20-bold" {...props}></Icon>
