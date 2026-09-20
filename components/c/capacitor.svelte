<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q23zuob8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path paint-order="fill markers stroke" class="q23zuob8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:capacitor" {...props}></Icon>
