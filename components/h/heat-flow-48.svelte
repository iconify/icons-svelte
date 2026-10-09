<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuvrmqbix.css';
import '../../css/z/z2tgbdc9c.css';
import '../../css/q/q3_ql_27a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iuvrmqbix"/><path class="z2tgbdc9c"/><path class="q3_ql_27a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-flow-48" {...props}></Icon>
