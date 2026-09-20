<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyqotpbcg.css';
import '../../css/s/sln3okb-w.css';
import '../../css/g/g2y24gmro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="lyqotpbcg"><rect class="sln3okb-w"/><path class="g2y24gmro"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:mic-alt-duotone" {...props}></Icon>
