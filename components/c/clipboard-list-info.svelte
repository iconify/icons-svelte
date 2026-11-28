<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlrx-lbei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tlrx-lbei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:clipboard-list-info" {...props}></Icon>
