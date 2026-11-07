<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aoj597b8y.css';
import '../../css/l/lb_j2db8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aoj597b8y"/><path class="lb_j2db8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:power-outline" {...props}></Icon>
