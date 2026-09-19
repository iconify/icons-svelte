<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8987domc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8987domc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulb-lightguide-flask" {...props}></Icon>
