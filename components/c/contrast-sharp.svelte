<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq8haq6el.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cq8haq6el"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:contrast-sharp" {...props}></Icon>
