<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br_smg_dn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="br_smg_dn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rocket-2-fill" {...props}></Icon>
