<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/e/ekzm7mbgd.css';
import '../../css/c/cqmb2skun.css';
import '../../css/h/hcum_-5kb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ekzm7mbgd"/><path class="cqmb2skun"/><path class="hcum_-5kb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:copy-success" {...props}></Icon>
