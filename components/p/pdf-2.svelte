<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/l/li1o8oboq.css';
import '../../css/v/vo56_7bsj.css';
import '../../css/b/b5eiaibvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="li1o8oboq"/><path class="vo56_7bsj"/><path class="b5eiaibvu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:pdf-2" {...props}></Icon>
