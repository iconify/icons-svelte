<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqxmsm42o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bqxmsm42o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:database-setting-remix" {...props}></Icon>
