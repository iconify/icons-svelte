<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9b945bdq.css';
import '../../css/n/n3pztie1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9b945bdq"/><path class="n3pztie1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:play-circle-fill" {...props}></Icon>
