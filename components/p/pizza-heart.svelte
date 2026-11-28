<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej_68dbsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ej_68dbsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:pizza-heart" {...props}></Icon>
