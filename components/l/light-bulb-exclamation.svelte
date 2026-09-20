<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuqogfllb.css';
import '../../css/z/z2amuho-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kuqogfllb"/><path clip-rule="evenodd" class="z2amuho-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:light-bulb-exclamation" {...props}></Icon>
