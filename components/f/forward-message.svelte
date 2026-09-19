<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/ds4dt58hw.css';
import '../../css/g/g-js9qb0w.css';
import '../../css/k/kl6dl5bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ds4dt58hw"/><path class="g-js9qb0w"/><path class="kl6dl5bmn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:forward-message" {...props}></Icon>
