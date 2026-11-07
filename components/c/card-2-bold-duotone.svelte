<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipje62d_x.css';
import '../../css/n/n65xcybdr.css';
import '../../css/v/v75m4zb9g.css';
import '../../css/t/tuasagb-m.css';
import '../../css/s/s6qd-zbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ipje62d_x"/><path clip-rule="evenodd" class="n65xcybdr"/><path class="v75m4zb9g"/><path class="tuasagb-m"/><path class="s6qd-zbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:card-2-bold-duotone" {...props}></Icon>
