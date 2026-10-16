<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa8mtjico.css';
import '../../css/x/xs22834vg.css';
import '../../css/v/v4yfn2nbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pa8mtjico"/><path class="xs22834vg"/><path class="v4yfn2nbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:aluminium-48" {...props}></Icon>
