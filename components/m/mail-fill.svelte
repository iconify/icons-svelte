<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xub61jorw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xub61jorw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mail-fill" {...props}></Icon>
