<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fhikcfy3j.css';
import '../../css/e/emoy9fbht.css';
import '../../css/j/j6nkprbzi.css';
import '../../css/q/qdk3eyjsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fhikcfy3j"/><path class="emoy9fbht"/><path class="j6nkprbzi"/><path class="qdk3eyjsk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:clipboard-check-duotone" {...props}></Icon>
