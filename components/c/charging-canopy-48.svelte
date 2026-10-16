<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgupoibyg.css';
import '../../css/k/krza2gbnk.css';
import '../../css/e/exrys5kfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rgupoibyg"/><path class="krza2gbnk"/><path class="exrys5kfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charging-canopy-48" {...props}></Icon>
