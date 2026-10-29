<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhfqa5prw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhfqa5prw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:book-open" {...props}></Icon>
