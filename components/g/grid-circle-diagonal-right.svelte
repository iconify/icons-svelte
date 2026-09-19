<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le1mi88em.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="le1mi88em"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:grid-circle-diagonal-right" {...props}></Icon>
