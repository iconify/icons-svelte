<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5e5ikb2t.css';
import '../../css/w/w07hk-pry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5e5ikb2t"/><path class="w07hk-pry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:avocado" {...props}></Icon>
