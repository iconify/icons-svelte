<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpjjukh9y.css';
import '../../css/i/i21vf0uiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vpjjukh9y"/><path class="i21vf0uiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hammer-48" {...props}></Icon>
