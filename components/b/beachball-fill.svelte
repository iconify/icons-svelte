<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob2v0kohw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ob2v0kohw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:beachball-fill" {...props}></Icon>
