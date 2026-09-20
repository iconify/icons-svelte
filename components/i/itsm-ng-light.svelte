<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shya_ld1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="shya_ld1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:itsm-ng-light" {...props}></Icon>
