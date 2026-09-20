<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iusjz_bzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iusjz_bzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:database-settings" {...props}></Icon>
