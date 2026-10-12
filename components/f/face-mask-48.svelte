<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y153yih8p.css';
import '../../css/l/lxgy0sctt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y153yih8p"/><path class="lxgy0sctt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:face-mask-48" {...props}></Icon>
