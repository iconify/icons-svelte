<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy1_gac9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dy1_gac9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:egnyte-logo-block" {...props}></Icon>
