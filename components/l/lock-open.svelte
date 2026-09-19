<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smr1-ljyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="smr1-ljyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:lock-open" {...props}></Icon>
