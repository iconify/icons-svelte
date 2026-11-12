<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vep--kuru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vep--kuru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-talk-dark" {...props}></Icon>
