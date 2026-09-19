<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enxvapbkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="enxvapbkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:cube-alt-02" {...props}></Icon>
