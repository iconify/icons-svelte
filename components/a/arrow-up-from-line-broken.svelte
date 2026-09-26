<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/p/p-1nc6b6p.css';
import '../../css/n/n-e1qqb_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p-1nc6b6p"/><path class="n-e1qqb_j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-up-from-line-broken" {...props}></Icon>
