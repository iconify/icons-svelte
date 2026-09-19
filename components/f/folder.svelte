<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txzmh0bpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txzmh0bpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:folder" {...props}></Icon>
