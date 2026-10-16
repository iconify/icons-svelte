<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjiicgwoi.css';
import '../../css/i/iqro0lbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wjiicgwoi"/><path class="iqro0lbqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:blade-pitch-48" {...props}></Icon>
