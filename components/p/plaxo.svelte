<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuz0qtb9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xuz0qtb9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:plaxo" {...props}></Icon>
