<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oup5h469r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oup5h469r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:border-top" {...props}></Icon>
