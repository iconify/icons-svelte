<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/j/jp89slbwl.css';
import '../../css/j/jxl67pbry.css';
import '../../css/c/cgwv8rv8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><circle class="jp89slbwl"/><circle class="jxl67pbry"/><circle class="cgwv8rv8i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:more-horizontal" {...props}></Icon>
