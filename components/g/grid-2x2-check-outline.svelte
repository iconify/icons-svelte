<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln-hxshjc.css';
import '../../css/e/egi_o9bmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ln-hxshjc"/><path class="egi_o9bmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:grid-2x2-check-outline" {...props}></Icon>
