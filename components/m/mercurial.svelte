<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vju3v6b4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vju3v6b4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mercurial" {...props}></Icon>
