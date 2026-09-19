<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2zxfobyr.css';
import '../../css/q/q6ywlpbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2zxfobyr"/><path class="q6ywlpbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:eye-outline" {...props}></Icon>
