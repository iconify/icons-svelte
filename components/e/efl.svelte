<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk7xaiuxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wk7xaiuxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:efl" {...props}></Icon>
