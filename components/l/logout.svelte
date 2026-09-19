<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acl-8db1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="acl-8db1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:logout" {...props}></Icon>
