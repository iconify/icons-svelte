<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_d-0rb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p_d-0rb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:key-alt" {...props}></Icon>
