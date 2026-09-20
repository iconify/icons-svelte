<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wilx9023w.css';
import '../../css/d/dn6s-ubtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wilx9023w"/><path class="dn6s-ubtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:dependabot-24" {...props}></Icon>
