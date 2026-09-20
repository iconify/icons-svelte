<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgpxnbb2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgpxnbb2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:paddy-power" {...props}></Icon>
