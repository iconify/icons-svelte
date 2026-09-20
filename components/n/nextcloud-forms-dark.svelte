<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9s-e-3im.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b9s-e-3im"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-forms-dark" {...props}></Icon>
