<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khymdnb6j.css';
import '../../css/z/zjys3ecwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="khymdnb6j"/><path class="zjys3ecwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:humidity-48" {...props}></Icon>
