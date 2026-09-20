<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izdje66kq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="izdje66kq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:direction-alt-2-fill" {...props}></Icon>
