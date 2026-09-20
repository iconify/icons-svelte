<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl0v214ql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yl0v214ql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:money-bill-stack" {...props}></Icon>
