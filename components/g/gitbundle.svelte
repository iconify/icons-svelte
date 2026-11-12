<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-9jh2b_h.css';
import '../../css/l/l2dczz-db.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v-9jh2b_h"/><path class="l2dczz-db"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gitbundle" {...props}></Icon>
