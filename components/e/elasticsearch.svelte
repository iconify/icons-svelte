<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui5i-fbas.css';
import '../../css/r/r6cuzyb1s.css';
import '../../css/l/l_h-rg3md.css';
import '../../css/l/lt41wmb7n.css';
import '../../css/n/ne65lbbag.css';
import '../../css/d/df5n5pb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ui5i-fbas"/><path class="r6cuzyb1s"/><path class="l_h-rg3md"/><path class="lt41wmb7n"/><path class="ne65lbbag"/><path class="df5n5pb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:elasticsearch" {...props}></Icon>
