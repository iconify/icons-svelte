<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/k/kgo6dpbjf.css';
import '../../css/s/sx6hnebpa.css';
import '../../css/k/krh2erb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kgo6dpbjf"/><path class="sx6hnebpa"/><path class="krh2erb9t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:image-play" {...props}></Icon>
