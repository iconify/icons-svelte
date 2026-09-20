<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1fh3foma.css';
import '../../css/o/oj7hu3rce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1fh3foma"/><path class="oj7hu3rce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ccd" {...props}></Icon>
