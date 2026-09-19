<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/y/ygbplvbei.css';
import '../../css/c/cplpj-rbo.css';
import '../../css/u/uxhzhrb1u.css';
import '../../css/h/hi65sfm0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="ygbplvbei"/><circle class="cplpj-rbo"/><path class="uxhzhrb1u"/><path class="hi65sfm0x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:microphone-one" {...props}></Icon>
