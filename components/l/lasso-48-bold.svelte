<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lydoh1n-z.css';
import '../../css/l/laty4l76k.css';
import '../../css/k/k_8z-tbww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lydoh1n-z"/><path class="laty4l76k"/><path class="k_8z-tbww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lasso-48-bold" {...props}></Icon>
