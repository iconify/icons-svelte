<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz1lfe28c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lz1lfe28c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:export" {...props}></Icon>
