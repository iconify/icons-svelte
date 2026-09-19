<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/vm8ob7cuz.css';
import '../../css/v/vq51a2bep.css';
import '../../css/w/wwdkt39lk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vm8ob7cuz"/><path class="vq51a2bep"/><path class="wwdkt39lk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:linux" {...props}></Icon>
