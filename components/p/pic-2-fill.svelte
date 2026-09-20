<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb3ax495o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lb3ax495o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pic-2-fill" {...props}></Icon>
