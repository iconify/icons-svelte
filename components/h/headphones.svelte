<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/r/r43dgsbqa.css';
import '../../css/s/sgmbzabxq.css';
import '../../css/s/sgxw2e1xb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="r43dgsbqa"/><path class="sgmbzabxq"/><path class="sgxw2e1xb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:headphones" {...props}></Icon>
