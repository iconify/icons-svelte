<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itswxnbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="itswxnbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mail-open-fill" {...props}></Icon>
