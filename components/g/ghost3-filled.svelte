<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyf75iblm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tyf75iblm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ghost3-filled" {...props}></Icon>
