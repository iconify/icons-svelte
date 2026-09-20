<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agybke3bk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agybke3bk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-cny-line" {...props}></Icon>
