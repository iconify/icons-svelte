<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/o/olw30ybsu.css';
import '../../css/s/svyxxuxte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="olw30ybsu"/><path class="svyxxuxte"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:fingerprint-off" {...props}></Icon>
