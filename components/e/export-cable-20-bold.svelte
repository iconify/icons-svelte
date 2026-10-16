<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcim_2ucb.css';
import '../../css/a/amu1h0n4r.css';
import '../../css/p/pgvjdacxw.css';
import '../../css/g/ghp9deben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xcim_2ucb"/><path class="amu1h0n4r"/><path class="pgvjdacxw"/><path class="ghp9deben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:export-cable-20-bold" {...props}></Icon>
