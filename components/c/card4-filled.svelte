<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szr80mb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szr80mb7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:card4-filled" {...props}></Icon>
