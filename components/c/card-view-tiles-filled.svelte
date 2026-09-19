<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bls-2lq9o.css';
import '../../css/p/p5wivnb6o.css';
import '../../css/c/ces-s2pfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="bls-2lq9o"/><rect class="p5wivnb6o"/><path class="ces-s2pfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:card-view-tiles-filled" {...props}></Icon>
