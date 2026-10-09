<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mepn4fbee.css';
import '../../css/a/ahzwwmb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mepn4fbee"/><path class="ahzwwmb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:piggy-bank-48" {...props}></Icon>
