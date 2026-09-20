<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z089eybzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z089eybzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:mic3" {...props}></Icon>
