<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkpkc0b2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkpkc0b2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:phi" {...props}></Icon>
