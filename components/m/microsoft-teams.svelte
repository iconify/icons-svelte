<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/a/a1ibtdbnq.css';
import '../../css/a/ay6sqcctf.css';
import '../../css/w/w22cj2-bq.css';
import '../../css/r/rd5yq9v5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="a1ibtdbnq"/><circle class="ay6sqcctf"/><path class="w22cj2-bq"/><path class="rd5yq9v5n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:microsoft-teams" {...props}></Icon>
