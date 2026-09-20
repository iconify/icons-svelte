<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skeut9b6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skeut9b6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:octagon-fill" {...props}></Icon>
