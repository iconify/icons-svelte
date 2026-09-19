<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_2l-mb5b.css';
import '../../css/b/b5_hbpb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_2l-mb5b"/><path class="b5_hbpb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:background-filled" {...props}></Icon>
