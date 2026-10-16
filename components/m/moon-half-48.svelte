<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu_zzgnel.css';
import '../../css/y/ya6awqbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vu_zzgnel"/><path class="ya6awqbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:moon-half-48" {...props}></Icon>
