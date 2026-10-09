<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0loxh3qm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h0loxh3qm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:align-justify-48" {...props}></Icon>
