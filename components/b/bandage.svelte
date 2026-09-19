<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnf2tkbyn.css';
import '../../css/w/wu0j47nvj.css';
import '../../css/x/x2cdf-bez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bnf2tkbyn"/><path class="wu0j47nvj"/><path class="x2cdf-bez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:bandage" {...props}></Icon>
