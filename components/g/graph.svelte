<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifg97u3ia.css';
import '../../css/z/zu3tvtb-o.css';
import '../../css/u/uc8tngikx.css';
import '../../css/c/cmc75bc9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path clip-rule="evenodd" class="ifg97u3ia"/><path clip-rule="evenodd" class="zu3tvtb-o"/><path clip-rule="evenodd" class="uc8tngikx"/><path clip-rule="evenodd" class="cmc75bc9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-ui:graph" {...props}></Icon>
