<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpspd0b0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hpspd0b0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:bank-outlined" {...props}></Icon>
