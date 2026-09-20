<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb2xhv94q.css';
import '../../css/r/r-fuctb7v.css';
import '../../css/y/y8gsoobat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fb2xhv94q"/><path class="r-fuctb7v"/><path class="y8gsoobat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:history" {...props}></Icon>
