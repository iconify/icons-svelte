<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx-bgzb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx-bgzb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:phone-incoming" {...props}></Icon>
