<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsfq8unvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qsfq8unvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:car" {...props}></Icon>
