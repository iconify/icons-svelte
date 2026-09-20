<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5rgy14zu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5rgy14zu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:arrow-up-left-24" {...props}></Icon>
