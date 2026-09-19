<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s03_u5bza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s03_u5bza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-wechat" {...props}></Icon>
