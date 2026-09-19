<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmhjqwmsl.css';
import '../../css/r/r56ofqbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmhjqwmsl"/><path clip-rule="evenodd" class="r56ofqbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:box-outline" {...props}></Icon>
