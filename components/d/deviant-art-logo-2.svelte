<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k14xmiymw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k14xmiymw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:deviant-art-logo-2" {...props}></Icon>
