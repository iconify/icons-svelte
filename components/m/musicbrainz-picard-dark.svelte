<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy4ogql_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xy4ogql_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:musicbrainz-picard-dark" {...props}></Icon>
