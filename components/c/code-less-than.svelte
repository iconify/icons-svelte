<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdwzo6u-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdwzo6u-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:code-less-than" {...props}></Icon>
