<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqxthabju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bqxthabju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mailgun-dark" {...props}></Icon>
