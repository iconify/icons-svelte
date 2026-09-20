<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgv0j_bwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgv0j_bwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-guardian" {...props}></Icon>
