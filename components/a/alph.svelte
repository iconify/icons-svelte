<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-am5se9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-am5se9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:alph" {...props}></Icon>
