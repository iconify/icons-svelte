<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftg7u_q6r.css';
import '../../css/c/ce_1shb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftg7u_q6r"/><path class="ce_1shb3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chevrons-up-down-outline" {...props}></Icon>
