<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko6i3z5qf.css';
import '../../css/o/oowixtbky.css';
import '../../css/t/tggvt9bno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ko6i3z5qf"/><path class="oowixtbky"/><path class="tggvt9bno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:lat" {...props}></Icon>
