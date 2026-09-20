<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aoo-m9bse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aoo-m9bse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:configuration-safety" {...props}></Icon>
