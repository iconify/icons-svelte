<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-1zzmbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="v-1zzmbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:monitor-outlined" {...props}></Icon>
