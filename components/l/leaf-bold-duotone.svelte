<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt9f2zz1g.css';
import '../../css/r/ry4h5fb7w.css';
import '../../css/i/iq4y8qctn.css';
import '../../css/k/kquyjabxs.css';
import '../../css/p/pczff7gss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nt9f2zz1g"/><path class="ry4h5fb7w"/><path class="iq4y8qctn"/><path class="kquyjabxs"/><path class="pczff7gss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:leaf-bold-duotone" {...props}></Icon>
