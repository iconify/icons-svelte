<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex9s0kk5d.css';
import '../../css/p/pvjrmx88k.css';
import '../../css/l/l7w7mb29j.css';
import '../../css/f/f9ihxbcgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="ex9s0kk5d"/><path class="pvjrmx88k"/><path class="l7w7mb29j"/><path class="f9ihxbcgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:kyrgyzstan" {...props}></Icon>
