<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un0prhb_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="un0prhb_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:checkmark" {...props}></Icon>
