<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp0-z8bbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pp0-z8bbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dmtr" {...props}></Icon>
