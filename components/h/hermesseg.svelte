<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg1-4zbux.css';
import '../../css/f/fdh0m_b1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="lg1-4zbux"/><path class="fdh0m_b1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hermesseg" {...props}></Icon>
