<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/g/g-o6a2-ay.css';
import '../../css/l/lor0dobsk.css';
import '../../css/u/u91wj2bhd.css';
import '../../css/y/ywomxlbes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><rect class="g-o6a2-ay"/><rect class="lor0dobsk"/><rect class="u91wj2bhd"/><circle class="ywomxlbes"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:application" {...props}></Icon>
