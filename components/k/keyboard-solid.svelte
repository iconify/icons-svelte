<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o10ka4bnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o10ka4bnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:keyboard-solid" {...props}></Icon>
