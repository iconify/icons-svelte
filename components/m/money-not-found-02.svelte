<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/j/jc_7zfapj.css';
import '../../css/w/wber-hsua.css';
import '../../css/o/ope6mwbtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jc_7zfapj"/><path class="wber-hsua"/><path class="ope6mwbtt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:money-not-found-02" {...props}></Icon>
