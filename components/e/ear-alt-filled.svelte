<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui0ex75nu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ui0ex75nu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:ear-alt-filled" {...props}></Icon>
