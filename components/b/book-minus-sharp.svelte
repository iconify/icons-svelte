<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi94aubdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zi94aubdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:book-minus-sharp" {...props}></Icon>
