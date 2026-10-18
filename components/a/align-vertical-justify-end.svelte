<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bejip4b3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bejip4b3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:align-vertical-justify-end" {...props}></Icon>
