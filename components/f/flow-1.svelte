<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea2dqbclq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ea2dqbclq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:flow-1" {...props}></Icon>
