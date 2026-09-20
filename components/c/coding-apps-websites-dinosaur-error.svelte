<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb66y-qhg.css';
import '../../css/k/kxh3svikf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fb66y-qhg"/><path class="kxh3svikf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:coding-apps-websites-dinosaur-error" {...props}></Icon>
