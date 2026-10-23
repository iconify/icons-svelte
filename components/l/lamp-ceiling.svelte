<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aty9q57nw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aty9q57nw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:lamp-ceiling" {...props}></Icon>
