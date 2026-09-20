<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg3k_nb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qg3k_nb0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:dice-5-solid" {...props}></Icon>
