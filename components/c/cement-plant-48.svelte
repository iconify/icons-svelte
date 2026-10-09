<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz0b40bzk.css';
import '../../css/x/xu6_eqb1f.css';
import '../../css/c/c65-ehvfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kz0b40bzk"/><path class="xu6_eqb1f"/><path class="c65-ehvfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cement-plant-48" {...props}></Icon>
