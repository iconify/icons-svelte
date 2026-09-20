<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d040dn-8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d040dn-8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:navigation-bolt" {...props}></Icon>
