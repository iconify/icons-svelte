<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/n/n1c5y3bdo.css';
import '../../css/a/avue01box.css';
import '../../css/e/empys87bl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n1c5y3bdo"/><path class="avue01box"/><path class="empys87bl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:recovery-mail" {...props}></Icon>
