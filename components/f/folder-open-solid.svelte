<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/biy8w7b2k.css';
import '../../css/g/gq5qxpyae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="biy8w7b2k"/><path class="gq5qxpyae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:folder-open-solid" {...props}></Icon>
