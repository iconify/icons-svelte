<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6xh5bbvt.css';
import '../../css/d/df_pnlkgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d6xh5bbvt"/><path class="df_pnlkgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:compass-duotone-line" {...props}></Icon>
