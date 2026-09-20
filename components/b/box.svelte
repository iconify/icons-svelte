<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr6vb84ov.css';
import '../../css/k/kdw9f6x7v.css';
import '../../css/m/mu_a5xqvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cr6vb84ov"/><path class="kdw9f6x7v"/><path class="mu_a5xqvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:box" {...props}></Icon>
