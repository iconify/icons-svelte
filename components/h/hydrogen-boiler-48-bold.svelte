<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zanasbbem.css';
import '../../css/d/dgdz7cczj.css';
import '../../css/j/jvxstphxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zanasbbem"/><path class="dgdz7cczj"/><path class="jvxstphxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-boiler-48-bold" {...props}></Icon>
