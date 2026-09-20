<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebng0rb1m.css';
import '../../css/t/tevsa0mrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebng0rb1m"/><path class="tevsa0mrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:music-square-fill" {...props}></Icon>
