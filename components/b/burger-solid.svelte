<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/biljftzdn.css';
import '../../css/c/cg2ro0qum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="biljftzdn"/><path clip-rule="evenodd" class="cg2ro0qum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:burger-solid" {...props}></Icon>
