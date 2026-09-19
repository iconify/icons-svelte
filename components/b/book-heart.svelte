<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idif-zbrp.css';
import '../../css/i/ivt8o-bva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idif-zbrp"/><path class="ivt8o-bva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:book-heart" {...props}></Icon>
