<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-171nr1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-171nr1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:left-indent-alt" {...props}></Icon>
