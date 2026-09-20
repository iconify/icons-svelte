<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3v8b3bbr.css';
import '../../css/o/onhszcbsu.css';
import '../../css/l/lwca995sk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3v8b3bbr"/><path class="onhszcbsu"/><path class="lwca995sk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:brn" {...props}></Icon>
