<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvm67acjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvm67acjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:card-sim-fill" {...props}></Icon>
