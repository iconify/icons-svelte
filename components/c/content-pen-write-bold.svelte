<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw9bk3v8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qw9bk3v8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:content-pen-write-bold" {...props}></Icon>
