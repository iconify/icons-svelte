<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csm3j--no.css';
import '../../css/b/bqw6zx0lk.css';
import '../../css/t/t8c3f1o7j.css';
import '../../css/f/fyarqiefq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="csm3j--no"/><path class="bqw6zx0lk"/><path class="t8c3f1o7j"/><path class="fyarqiefq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fuel-oil-tank-48" {...props}></Icon>
