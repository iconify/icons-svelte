<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve7dckibf.css';
import '../../css/d/dl48ttr9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ve7dckibf"/><path class="dl48ttr9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hair-dryer-48-bold" {...props}></Icon>
