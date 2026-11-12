<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljh46-15w.css';
import '../../css/p/p9i-ec0lv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ljh46-15w"/><path class="p9i-ec0lv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:flux-operator-dark" {...props}></Icon>
