<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn3wpqudq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="dn3wpqudq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:file-vector-small-filled" {...props}></Icon>
