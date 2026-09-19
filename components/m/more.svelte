<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djr264bkf.css';
import '../../css/k/kb4k8nblj.css';
import '../../css/c/c0pinfbcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="djr264bkf"/><path class="kb4k8nblj"/><path class="c0pinfbcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:more" {...props}></Icon>
