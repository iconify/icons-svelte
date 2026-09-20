<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/sa6gy3ztr.css';
import '../../css/n/n3fmk5byk.css';
import '../../css/b/b6enbdbml.css';
import '../../css/n/n5shqk82c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sa6gy3ztr"/><path class="n3fmk5byk"/><path class="b6enbdbml"/><path class="n5shqk82c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mouse-circle-broken" {...props}></Icon>
