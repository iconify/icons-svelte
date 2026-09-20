<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9cjbac7h.css';
import '../../css/s/sakiijw5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n9cjbac7h"/><path class="sakiijw5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:aviato-light" {...props}></Icon>
