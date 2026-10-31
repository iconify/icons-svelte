<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn4bc_bdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qn4bc_bdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:indent-solid" {...props}></Icon>
