<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/i/isarv1pye.css';
import '../../css/t/twfn4lxjv.css';
import '../../css/e/eya-shbjw.css';
import '../../css/f/fpw3n5gpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="isarv1pye"/><path class="twfn4lxjv"/><path class="eya-shbjw"/><path class="fpw3n5gpe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:calculator-1-flat" {...props}></Icon>
