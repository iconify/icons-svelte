<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtajz45ww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qtajz45ww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-plus-logo-2" {...props}></Icon>
