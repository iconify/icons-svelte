<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/biljftzdn.css';
import '../../css/s/s4-6ofb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="biljftzdn"/><path clip-rule="evenodd" class="s4-6ofb6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:burger-light" {...props}></Icon>
