<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/accb4rb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="accb4rb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:app-store-solid" {...props}></Icon>
