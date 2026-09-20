<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpuf-gb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpuf-gb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:asterisk" {...props}></Icon>
