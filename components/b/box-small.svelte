<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lywu_-b-a.css';
import '../../css/b/bvqviuxxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lywu_-b-a"/><path class="bvqviuxxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:box-small" {...props}></Icon>
