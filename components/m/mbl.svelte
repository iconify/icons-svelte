<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3dnj8n0d.css';
import '../../css/z/zsrd_jbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3dnj8n0d"/><path class="zsrd_jbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mbl" {...props}></Icon>
