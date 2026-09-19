<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo-s3h8ki.css';
import '../../css/z/zfwtadppq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oo-s3h8ki"/><path class="zfwtadppq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:hospital-1" {...props}></Icon>
