<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq9rqn1zt.css';
import '../../css/r/rw5qbebuy.css';
import '../../css/n/nad7zgbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nq9rqn1zt"/><path class="rw5qbebuy"/><path class="nad7zgbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-bottom-open-bold-duotone" {...props}></Icon>
