<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krwo12_et.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krwo12_et"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:circle-outer-dashed-circle-filled" {...props}></Icon>
