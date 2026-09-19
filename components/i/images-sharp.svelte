<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/laopiwk5n.css';
import '../../css/n/nboie9b2d.css';
import '../../css/b/bfjxetbbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="laopiwk5n"/><path class="nboie9b2d"/><path class="bfjxetbbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:images-sharp" {...props}></Icon>
