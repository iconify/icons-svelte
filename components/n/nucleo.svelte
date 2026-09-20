<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayi46kkzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ayi46kkzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:nucleo" {...props}></Icon>
