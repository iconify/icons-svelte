<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv_bb_ldv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kv_bb_ldv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:git-branch-solid" {...props}></Icon>
