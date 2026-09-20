<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuqt_yb-q.css';
import '../../css/c/c6sfqyboe.css';
import '../../css/x/xfpsz_bsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uuqt_yb-q"/><path class="c6sfqyboe"/><path class="xfpsz_bsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:plus-circle" {...props}></Icon>
