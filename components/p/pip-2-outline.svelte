<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh46y3bin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qh46y3bin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pip-2-outline" {...props}></Icon>
