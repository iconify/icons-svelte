<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0tdvpgiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o0tdvpgiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:road-48" {...props}></Icon>
