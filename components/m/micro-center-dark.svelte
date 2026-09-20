<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/megucjbvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="megucjbvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:micro-center-dark" {...props}></Icon>
