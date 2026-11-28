<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv_lgoapu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary xv_lgoapu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pliers-duotone" {...props}></Icon>
