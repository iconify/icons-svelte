<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1aks1oms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q1aks1oms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:division-math-symbol-circle-bold" {...props}></Icon>
