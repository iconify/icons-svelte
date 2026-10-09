<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9znocb5r.css';
import '../../css/s/stcfx4bpj.css';
import '../../css/f/f5atepbej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q9znocb5r"/><path class="stcfx4bpj"/><path class="f5atepbej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pipeline-48-bold" {...props}></Icon>
