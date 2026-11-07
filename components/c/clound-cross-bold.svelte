<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3-vhnb6i.css';
import '../../css/j/jik0uqbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j3-vhnb6i"/><path class="jik0uqbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clound-cross-bold" {...props}></Icon>
