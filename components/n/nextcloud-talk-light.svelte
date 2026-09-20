<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5t43yc4z.css';
import '../../css/u/ucpf2webs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="v5t43yc4z"/><path clip-rule="evenodd" class="ucpf2webs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-talk-light" {...props}></Icon>
