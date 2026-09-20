<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihmgd-bza.css';
import '../../css/x/x9845bcgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihmgd-bza"/><path class="x9845bcgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:hzn" {...props}></Icon>
