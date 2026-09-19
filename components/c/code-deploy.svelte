<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0gbg4buk.css';
import '../../css/n/njpi2rhkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0gbg4buk"/><path class="njpi2rhkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:code-deploy" {...props}></Icon>
