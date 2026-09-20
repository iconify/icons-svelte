<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g66tgxbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g66tgxbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-office-document" {...props}></Icon>
