<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoyo56b2a.css';
import '../../css/o/ogduviblr.css';
import '../../css/b/bx9w9rkcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xoyo56b2a"/><path class="ogduviblr"/><path class="bx9w9rkcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mrs" {...props}></Icon>
