<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjwnci-_l.css';
import '../../css/i/izsswccel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjwnci-_l"/><path class="izsswccel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:cross-reference-24" {...props}></Icon>
