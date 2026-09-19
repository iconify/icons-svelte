<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex3a4wbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ex3a4wbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:plus-minus" {...props}></Icon>
