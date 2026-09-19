<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zao2phbdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="zao2phbdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:kaldi-wordmark" {...props}></Icon>
