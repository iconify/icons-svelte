<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1rkvo-db.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x1rkvo-db"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:limesurvey-light" {...props}></Icon>
