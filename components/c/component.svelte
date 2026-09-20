<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/z/zo8mk2bnn.css';
import '../../css/t/tt1d5565u.css';
import '../../css/h/hfsfznb3n.css';
import '../../css/f/f4_v000vi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect transform="rotate(-45 7.99 17.86)" class="zo8mk2bnn"/><rect transform="rotate(-45 13.85 12)" class="tt1d5565u"/><rect transform="rotate(-45 2.13 12)" class="hfsfznb3n"/><rect transform="rotate(-45 7.99 6.14)" class="f4_v000vi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:component" {...props}></Icon>
