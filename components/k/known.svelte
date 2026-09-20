<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az94a4bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="az94a4bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:known" {...props}></Icon>
