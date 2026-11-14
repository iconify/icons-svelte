<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbbp588xj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hbbp588xj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:money-bag-01" {...props}></Icon>
