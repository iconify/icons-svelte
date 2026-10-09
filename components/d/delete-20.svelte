<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2pyevbzu.css';
import '../../css/n/n4-5ir_js.css';
import '../../css/m/maa-xwdby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g2pyevbzu"/><path class="n4-5ir_js"/><path class="maa-xwdby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:delete-20" {...props}></Icon>
