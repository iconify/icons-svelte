<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bg2ies3lk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bg2ies3lk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:crowdsec-dark" {...props}></Icon>
