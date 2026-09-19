<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m640nac0w.css';
import '../../css/b/bbh__hbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="m640nac0w"/><path class="bbh__hbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:rotate-right-outlined" {...props}></Icon>
