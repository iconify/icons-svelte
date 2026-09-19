<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/n/n3e2bl-1s.css';
import '../../css/k/kozsdpb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="logout-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="n3e2bl-1s"/><path class="kozsdpb7i"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:logout-outline" {...props}></Icon>
