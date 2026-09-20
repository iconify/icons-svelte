<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qeq6vdblg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qeq6vdblg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:planet" {...props}></Icon>
