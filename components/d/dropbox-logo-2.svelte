<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8df1obis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8df1obis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:dropbox-logo-2" {...props}></Icon>
