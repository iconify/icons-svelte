<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh-g3b15f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bh-g3b15f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:citroen" {...props}></Icon>
