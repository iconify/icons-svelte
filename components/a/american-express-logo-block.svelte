<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnys6xy_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pnys6xy_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:american-express-logo-block" {...props}></Icon>
