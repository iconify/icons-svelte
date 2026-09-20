<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx3y42bar.css';
import '../../css/b/bub6_kbew.css';
import '../../css/f/f9dyx4nnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx3y42bar"/><path class="bub6_kbew"/><path class="f9dyx4nnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:movies-sit-drink-bold" {...props}></Icon>
