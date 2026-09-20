<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/d/dxrprw4rb.css';
import '../../css/r/rn0033ozd.css';
import '../../css/t/tbfod3hgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="dxrprw4rb"/><path class="rn0033ozd"/><rect class="tbfod3hgq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:arrow-down-square" {...props}></Icon>
