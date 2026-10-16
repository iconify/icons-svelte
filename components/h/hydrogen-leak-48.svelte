<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u43i3jb2i.css';
import '../../css/c/c9_dz4bmi.css';
import '../../css/m/m7e0bqrrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u43i3jb2i"/><path class="c9_dz4bmi"/><path class="m7e0bqrrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-leak-48" {...props}></Icon>
