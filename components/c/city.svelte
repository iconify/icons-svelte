<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmevdnb3h.css';
import '../../css/b/bw323sqaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmevdnb3h"/><path class="bw323sqaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:city" {...props}></Icon>
