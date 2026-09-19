<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aflt1xbkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aflt1xbkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:bolt" {...props}></Icon>
