<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-n5qac3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-n5qac3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:nu" {...props}></Icon>
