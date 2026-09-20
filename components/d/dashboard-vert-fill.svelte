<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jisctcszw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jisctcszw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:dashboard-vert-fill" {...props}></Icon>
