<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-y1qabka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v-y1qabka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-contacts-light" {...props}></Icon>
