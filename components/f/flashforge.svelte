<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj6jh_bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jj6jh_bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:flashforge" {...props}></Icon>
