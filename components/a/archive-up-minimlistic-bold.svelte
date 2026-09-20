<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d80rk9xbs.css';
import '../../css/q/qwayru87p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d80rk9xbs"/><path clip-rule="evenodd" class="qwayru87p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-up-minimlistic-bold" {...props}></Icon>
