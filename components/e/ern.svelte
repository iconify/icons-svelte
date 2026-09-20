<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aid4a4bsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aid4a4bsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ern" {...props}></Icon>
