<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjsgojboe.css';
import '../../css/f/f11gmybah.css';
import '../../css/v/vy8ukubtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sjsgojboe"/><path class="f11gmybah"/><path class="vy8ukubtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-low-48-bold" {...props}></Icon>
