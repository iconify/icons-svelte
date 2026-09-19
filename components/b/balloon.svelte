<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj81zpj-r.css';
import '../../css/n/nm_4mya7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bj81zpj-r"/><path class="nm_4mya7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:balloon" {...props}></Icon>
