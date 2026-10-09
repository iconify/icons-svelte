<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agva6viha.css';
import '../../css/m/mb4eqwb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="agva6viha"/><path class="mb4eqwb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chef-knife-20-bold" {...props}></Icon>
