<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya2xpubcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ya2xpubcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:copyright-filled" {...props}></Icon>
