<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgxo9gb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path class="lgxo9gb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-qq-filled" {...props}></Icon>
