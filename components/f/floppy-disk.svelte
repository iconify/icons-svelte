<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwan5id-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwan5id-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:floppy-disk" {...props}></Icon>
