<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp5pszbjw.css';
import '../../css/m/mp7d1bc8d.css';
import '../../css/q/qohtrw29d.css';
import '../../css/n/ndl2skddu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tp5pszbjw"><path class="mp7d1bc8d"/><path class="qohtrw29d"/><path clip-rule="evenodd" class="ndl2skddu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nousresearch-hermes" {...props}></Icon>
