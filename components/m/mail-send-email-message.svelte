<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmgpc8afi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jmgpc8afi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:mail-send-email-message" {...props}></Icon>
