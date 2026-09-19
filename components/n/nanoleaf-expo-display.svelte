<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn81uccvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pn81uccvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nanoleaf-expo-display" {...props}></Icon>
