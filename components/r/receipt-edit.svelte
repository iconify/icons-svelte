<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/y/yjvt5mqru.css';
import '../../css/y/y9njoccth.css';
import '../../css/t/t5kr6cgli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yjvt5mqru"/><path class="y9njoccth"/><path class="t5kr6cgli"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:receipt-edit" {...props}></Icon>
