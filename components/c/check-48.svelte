<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p29i2lbbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p29i2lbbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:check-48" {...props}></Icon>
