<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh-bklb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gh-bklb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bifi" {...props}></Icon>
