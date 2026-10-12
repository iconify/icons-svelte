<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg03hcbot.css';
import '../../css/y/ybe7dm20u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gg03hcbot"/><path class="ybe7dm20u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gearbox-48-bold" {...props}></Icon>
