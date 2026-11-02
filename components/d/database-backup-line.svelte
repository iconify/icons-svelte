<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arg93t4-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="arg93t4-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:database-backup-line" {...props}></Icon>
