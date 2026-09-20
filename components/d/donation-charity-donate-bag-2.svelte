<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/p/p94_bsqsn.css';
import '../../css/s/s4tzz1xjy.css';
import '../../css/k/k7i5r8b-m.css';
import '../../css/b/buvterbpv.css';
import '../../css/v/v6a9_t-6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="p94_bsqsn"/><path class="s4tzz1xjy"/><path class="k7i5r8b-m"/><path class="buvterbpv"/><path class="v6a9_t-6q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:donation-charity-donate-bag-2" {...props}></Icon>
