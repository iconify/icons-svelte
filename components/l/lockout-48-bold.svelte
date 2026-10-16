<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-9uribkc.css';
import '../../css/k/kl96fjb_a.css';
import '../../css/z/zj2jh3sfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k-9uribkc"/><path class="kl96fjb_a"/><path class="zj2jh3sfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lockout-48-bold" {...props}></Icon>
