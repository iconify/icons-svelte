<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/d/df6p8rh7a.css';
import '../../css/i/ijxzg4bdd.css';
import '../../css/m/md2eyrs9r.css';
import '../../css/b/byr4zob5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="df6p8rh7a wm-k"/><path class="ijxzg4bdd wm-a"/><path class="md2eyrs9r"/><path class="byr4zob5j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:cherry" {...props}></Icon>
