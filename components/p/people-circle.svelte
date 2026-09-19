<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-jv-mbrm.css';
import '../../css/t/t5-bpgztj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b-jv-mbrm"/><path class="t5-bpgztj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:people-circle" {...props}></Icon>
