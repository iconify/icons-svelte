<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw3rkdb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tw3rkdb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:buildings-fill" {...props}></Icon>
