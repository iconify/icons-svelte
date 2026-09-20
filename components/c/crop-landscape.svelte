<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adm28hbce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adm28hbce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:crop-landscape" {...props}></Icon>
