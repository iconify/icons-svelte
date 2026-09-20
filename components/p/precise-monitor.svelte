<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpo_bc98z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xpo_bc98z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:precise-monitor" {...props}></Icon>
