<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftv6d47py.css';
import '../../css/k/kaj68m1tu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ftv6d47py"/><path class="kaj68m1tu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:model-reference" {...props}></Icon>
