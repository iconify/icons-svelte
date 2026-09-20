<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3r63-bok.css';
import '../../css/x/x53871j6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k3r63-bok"/><path class="x53871j6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:coffee-bean-solid" {...props}></Icon>
