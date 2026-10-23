<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/q/qhyii4brw.css';
import '../../css/p/ppbdtfbyp.css';
import '../../css/u/ukce0gr5b.css';
import '../../css/v/vluk53bvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="qhyii4brw"/><path class="ppbdtfbyp"/><path class="ukce0gr5b"/><path class="vluk53bvz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:alarm-clock" {...props}></Icon>
