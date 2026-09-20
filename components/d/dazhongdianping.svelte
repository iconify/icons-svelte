<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygcli8bhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygcli8bhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:dazhongdianping" {...props}></Icon>
