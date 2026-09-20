<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj19krb9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mj19krb9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:boat-rental" {...props}></Icon>
