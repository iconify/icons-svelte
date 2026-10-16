<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wffgbluit.css';
import '../../css/g/gl49t146u.css';
import '../../css/s/s5hl0o4ib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wffgbluit"/><path class="gl49t146u"/><path class="s5hl0o4ib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:brick-wall-48-bold" {...props}></Icon>
