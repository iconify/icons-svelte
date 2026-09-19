<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8bnl6wke.css';
import '../../css/z/zy6g27b_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path clip-rule="evenodd" class="m8bnl6wke"/><path clip-rule="evenodd" class="zy6g27b_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-ui:iphone" {...props}></Icon>
