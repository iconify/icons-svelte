<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqsohmzgt.css';
import '../../css/p/pb4gmv60s.css';
import '../../css/m/millydbar.css';
import '../../css/h/hdqko0boa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="iqsohmzgt"/><path class="pb4gmv60s"/><path class="millydbar"/><path class="hdqko0boa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:rosemary" {...props}></Icon>
