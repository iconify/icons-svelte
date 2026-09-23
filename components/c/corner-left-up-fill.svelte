<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8r5mgc6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8r5mgc6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:corner-left-up-fill" {...props}></Icon>
