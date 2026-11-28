<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va2qw5bsc.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/g41oqhzpy.css';
import '../../css/i/ixg3tzbda.css';
import '../../css/s/s4sut7bjd.css';
import '../../css/k/kspf9vbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary va2qw5bsc"/><g class="dt0cm9dhy primary"><path class="g41oqhzpy"/><path class="ixg3tzbda"/><path class="s4sut7bjd"/><path class="kspf9vbor"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-symlink-duo" {...props}></Icon>
