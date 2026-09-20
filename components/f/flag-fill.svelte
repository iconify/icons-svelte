<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ney9ldy-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ney9ldy-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:flag-fill" {...props}></Icon>
