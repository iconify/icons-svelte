<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjsgojboe.css';
import '../../css/f/f11gmybah.css';
import '../../css/d/dn8te6s6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sjsgojboe"/><path class="f11gmybah"/><path class="dn8te6s6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-full-48-bold" {...props}></Icon>
