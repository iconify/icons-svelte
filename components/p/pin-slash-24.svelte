<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygm273o1e.css';
import '../../css/f/frppt49pm.css';
import '../../css/f/f6krerb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygm273o1e"/><path class="frppt49pm"/><path class="f6krerb0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:pin-slash-24" {...props}></Icon>
