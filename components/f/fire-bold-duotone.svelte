<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wole6hbze.css';
import '../../css/e/egno4qbun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wole6hbze"/><path class="egno4qbun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:fire-bold-duotone" {...props}></Icon>
