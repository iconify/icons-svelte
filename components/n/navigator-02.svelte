<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/o/ocdg62b7r.css';
import '../../css/p/pmgkdmbqo.css';
import '../../css/x/x1-s1-bdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ocdg62b7r"/><path class="pmgkdmbqo"/><path class="x1-s1-bdk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:navigator-02" {...props}></Icon>
