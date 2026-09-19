<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9qdzubor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9qdzubor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:paramount" {...props}></Icon>
