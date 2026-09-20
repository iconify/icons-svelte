<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de1zgmdha.css';
import '../../css/j/jloulibzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="de1zgmdha"/><path clip-rule="evenodd" class="jloulibzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:leaf-duotone" {...props}></Icon>
