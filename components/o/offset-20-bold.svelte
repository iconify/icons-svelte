<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9in_db-o.css';
import '../../css/i/ivhqrxbjl.css';
import '../../css/o/ov0i-wazh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w9in_db-o"/><path class="ivhqrxbjl"/><path class="ov0i-wazh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:offset-20-bold" {...props}></Icon>
