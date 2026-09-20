<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz0uj0bdt.css';
import '../../css/b/bn449xbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pz0uj0bdt"/><path class="bn449xbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:envelope-solid" {...props}></Icon>
