<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdyia779g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rdyia779g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dovecot" {...props}></Icon>
