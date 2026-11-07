<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygr0q7bwz.css';
import '../../css/o/opxxwacjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygr0q7bwz"/><path class="opxxwacjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chair-bold" {...props}></Icon>
