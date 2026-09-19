<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbsiz1bro.css';
import '../../css/j/jt_ac1zjj.css';
import '../../css/c/c5zqg9bcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="fbsiz1bro"/><path class="jt_ac1zjj"/><path class="c5zqg9bcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:bg-4x3" {...props}></Icon>
