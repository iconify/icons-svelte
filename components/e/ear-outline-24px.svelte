<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufb_vyhbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ufb_vyhbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ear-outline-24px" {...props}></Icon>
