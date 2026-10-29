<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1r7a7bnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1r7a7bnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:package-minus" {...props}></Icon>
