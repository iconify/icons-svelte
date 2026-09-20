<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sub8xtbuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sub8xtbuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:key-square" {...props}></Icon>
