<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzdiky75l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzdiky75l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:phone-actions-refresh-bold" {...props}></Icon>
