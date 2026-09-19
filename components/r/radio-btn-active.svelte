<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb-tdob4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mb-tdob4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:radio-btn-active" {...props}></Icon>
