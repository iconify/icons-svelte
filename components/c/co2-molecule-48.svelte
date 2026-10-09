<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvx5cvkbp.css';
import '../../css/o/ozmfki5en.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fvx5cvkbp"/><path class="ozmfki5en"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:co2-molecule-48" {...props}></Icon>
