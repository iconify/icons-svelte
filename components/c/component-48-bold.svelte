<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p61lf_73v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p61lf_73v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:component-48-bold" {...props}></Icon>
