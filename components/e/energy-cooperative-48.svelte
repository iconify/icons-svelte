<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec6pe6b-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ec6pe6b-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-cooperative-48" {...props}></Icon>
