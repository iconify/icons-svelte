<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj8ii1bcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qj8ii1bcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:presentation" {...props}></Icon>
