<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndoo8eizj.css';
import '../../css/f/fsi0i5btw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ndoo8eizj"/><path class="fsi0i5btw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gps-48" {...props}></Icon>
