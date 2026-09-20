<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja3mrtbir.css';
import '../../css/n/nmhwd39xk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="ja3mrtbir"/><path class="nmhwd39xk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:key-fill" {...props}></Icon>
