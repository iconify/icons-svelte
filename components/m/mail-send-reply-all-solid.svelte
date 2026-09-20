<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fva8p8ufs.css';
import '../../css/u/u9tojb6xh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fva8p8ufs"/><path class="u9tojb6xh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:mail-send-reply-all-solid" {...props}></Icon>
