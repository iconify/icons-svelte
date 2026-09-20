<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dan12lfgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dan12lfgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gamebanana" {...props}></Icon>
