<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfs3-mmpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfs3-mmpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:chevrons-up-down" {...props}></Icon>
