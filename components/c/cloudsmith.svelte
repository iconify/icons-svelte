<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncu15vb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ncu15vb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cloudsmith" {...props}></Icon>
