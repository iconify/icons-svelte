<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1a9uuxuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b1a9uuxuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:refresh-circle-solid" {...props}></Icon>
