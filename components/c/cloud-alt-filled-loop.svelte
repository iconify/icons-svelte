<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q31jsb.css';
import '../../css/d/d-gf8qwu.css';
import '../../css/s/so-from-60.css';
import '../../css/f/fill-to-1.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q31jsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:cloud-alt-filled-loop" {...props}></Icon>
