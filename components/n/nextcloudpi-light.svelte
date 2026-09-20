<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akmyxebxj.css';
import '../../css/z/zf1qckbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="akmyxebxj"/><path clip-rule="evenodd" class="zf1qckbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloudpi-light" {...props}></Icon>
