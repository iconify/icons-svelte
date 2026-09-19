<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty5wgbcxn.css';
import '../../css/d/di8rvibxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ty5wgbcxn"/><path class="di8rvibxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:car-key" {...props}></Icon>
