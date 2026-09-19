<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gako1acdl.css';
import '../../css/m/m_ynd7bgu.css';
import '../../css/b/b-xb5zbzp.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 gako1acdl"/><path class="clr-i-outline clr-i-outline-path-2 m_ynd7bgu"/><path class="b-xb5zbzp clr-i-outline clr-i-outline-path-3"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:filter-2-line" {...props}></Icon>
