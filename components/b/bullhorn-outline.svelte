<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd9w0yveu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pd9w0yveu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:bullhorn-outline" {...props}></Icon>
