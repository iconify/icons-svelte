<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbu_b2b4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbu_b2b4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-supabase" {...props}></Icon>
