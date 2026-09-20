<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jek51cc3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jek51cc3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:git-commit" {...props}></Icon>
