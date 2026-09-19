<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfh7s4zzd.css';
import '../../css/q/q6j6r4b5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="sfh7s4zzd"/><path class="q6j6r4b5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:jamstack-wordmark" {...props}></Icon>
