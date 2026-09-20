<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psh1nub4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psh1nub4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:qmall" {...props}></Icon>
