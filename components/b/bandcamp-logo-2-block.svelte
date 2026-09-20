<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-n60hb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a-n60hb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:bandcamp-logo-2-block" {...props}></Icon>
