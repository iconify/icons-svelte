<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyb8n-38v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fyb8n-38v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dovecot-light" {...props}></Icon>
