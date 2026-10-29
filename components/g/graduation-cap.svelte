<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/caw3fktbl.css';
import '../../css/k/k_3k7ab8h.css';
import '../../css/t/tsntq4fba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="caw3fktbl"/><path class="k_3k7ab8h"/><path class="tsntq4fba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:graduation-cap" {...props}></Icon>
