<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zixyvouym.css';
import '../../css/k/kbc9ywbnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zixyvouym"/><path class="kbc9ywbnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:domain-duotone" {...props}></Icon>
