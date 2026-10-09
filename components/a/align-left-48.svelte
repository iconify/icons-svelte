<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibbygoz8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ibbygoz8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:align-left-48" {...props}></Icon>
