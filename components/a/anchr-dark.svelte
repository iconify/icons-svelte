<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukhaiwb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ukhaiwb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:anchr-dark" {...props}></Icon>
