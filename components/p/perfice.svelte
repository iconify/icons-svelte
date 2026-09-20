<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqaaen3kj.css';
import '../../css/a/ac-8vg33b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nqaaen3kj"/><path class="ac-8vg33b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:perfice" {...props}></Icon>
