<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw5h3vgtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pw5h3vgtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:douban" {...props}></Icon>
