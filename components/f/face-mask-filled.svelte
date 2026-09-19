<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5ej4pbho.css';
import '../../css/c/c6etmkbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5ej4pbho"/><path class="c6etmkbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:face-mask-filled" {...props}></Icon>
