<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kckk9tsow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kckk9tsow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:alipay" {...props}></Icon>
