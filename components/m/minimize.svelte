<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyj-7ezxh.css';
import '../../css/q/q1n0ufkxq.css';
import '../../css/n/nofshwblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vyj-7ezxh wm-shadow"/><path class="q1n0ufkxq wm-k"/><path class="nofshwblh wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:minimize" {...props}></Icon>
