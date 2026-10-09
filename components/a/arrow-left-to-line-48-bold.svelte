<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xexqeacnw.css';
import '../../css/m/mpc5lgr0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xexqeacnw"/><path class="mpc5lgr0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-left-to-line-48-bold" {...props}></Icon>
