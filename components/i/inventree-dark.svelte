<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_t1g914s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v_t1g914s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:inventree-dark" {...props}></Icon>
