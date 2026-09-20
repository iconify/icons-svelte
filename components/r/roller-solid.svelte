<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz9kdgpzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kz9kdgpzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:roller-solid" {...props}></Icon>
