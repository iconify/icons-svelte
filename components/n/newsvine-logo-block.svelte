<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bplqn1p5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bplqn1p5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:newsvine-logo-block" {...props}></Icon>
