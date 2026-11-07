<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewr0bdyvc.css';
import '../../css/l/ll7areqdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewr0bdyvc"/><path clip-rule="evenodd" class="ll7areqdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bell-off-outline" {...props}></Icon>
