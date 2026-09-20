<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv75wz1iz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tv75wz1iz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mattermost-dark" {...props}></Icon>
