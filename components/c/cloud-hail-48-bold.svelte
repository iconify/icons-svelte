<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h61y6nb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h61y6nb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-hail-48-bold" {...props}></Icon>
